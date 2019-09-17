max-path-step: 5000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
imitation-weight: 0.5
total-step-num: 2500000000
HLC-frequency: 25
render-eval: False
loss-output-bound-coeff: 0.0
squash-action: True
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-step-num: 5000000
task-weight: 0.5
expert-num: 4
filter-action: True
prioritized-exp-replay: True
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
critic-layer-size: [256, 256]
action-dim: 12
critic-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-l2-reg: 0.0003
replay-ratio: 1
max-path-num: 20
bullet-default-PD: False
filter-torque: False
critic-l2-reg: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
test-num: 4
max-train-time: 10
replay-buffer-size: 1000000
rollout-step-num: 1
loss-output-diff-coeff: 0
gating-layer-size: [32, 32]
gating-index: None
tau: 0.001
actor-weight-decay: 1e-06
expert-index: None
reward-scale: 0.1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
joint-interpolation: True
state-dim: 23
actor-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
gamma: 0.955
dsr-gait-period: 0.6
epoch-num: 500
Physics-frequency: 1000
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
max-episode-num: 5000000
replay-start-size: 10000
record-start-size: 10000.0
actor-lr: 0.0003
loss-entropy-coeff: 0.0
LLC-frequency: 500
env-id: HumanoidBalanceFilter-v0
max-step-num: 2500000000
critic-weight-decay: 1e-06
batch-size: 128
loss-output-smooth-coeff: 2.0
dsr-gait-freq: 1.667
gating-activation-fn: ['relu', 'relu', 'None']
