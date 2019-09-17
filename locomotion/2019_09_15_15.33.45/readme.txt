max-train-time: 10
HLC-frequency: 25
env-id: HumanoidBalanceFilter-v0
tau: 0.001
replay-buffer-size: 1000000
max-test-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
gating-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
state-dim: 23
loss-output-smooth-coeff: 2.0
bullet-default-PD: False
rollout-step-num: 1
task-weight: 0.5
gamma: 0.955
loss-output-diff-coeff: 0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
actor-layer-size: [256, 256]
filter-action: True
joint-interpolation: True
LLC-frequency: 500
n-step: 1
actor-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
epoch-num: 500
record-start-size: 10000.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
expert-num: 4
gating-layer-size: [32, 32]
train-step-num: 1
prioritized-exp-replay: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
imitation-weight: 0.5
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
replay-ratio: 1
total-step-num: 2500000000
loss-entropy-coeff: 0.0
squash-action: True
dsr-gait-freq: 1.667
max-episode-num: 5000000
loss-output-bound-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-layer-size: [256, 256]
reward-scale: 0.1
render-eval: False
dsr-gait-period: 0.6
test-num: 4
epoch-step-num: 5000000
gating-index: None
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
critic-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-torque: False
interpolation: False
critic-weight-decay: 1e-06
expert-index: None
actor-weight-decay: 1e-06
max-step-num: 2500000000
Physics-frequency: 1000
critic-l2-reg: 0.0003
action-dim: 12
