max-path-step: 5000
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
critic-layer-size: [256, 256]
loss-entropy-coeff: 0.0
expert-index: None
gating-layer-size: [32, 32]
HLC-frequency: 25
dsr-gait-freq: 1.667
action-dim: 12
actor-l2-reg: 0.0003
train-step-num: 1
replay-ratio: 1
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
expert-num: 4
test-num: 4
critic-lr: 0.0003
squash-action: True
epoch-num: 500
env-id: HumanoidBalanceFilter-v0
actor-layer-size: [256, 256]
actor-weight-decay: 1e-06
state-dim: 23
LLC-frequency: 500
task-weight: 0.5
max-train-time: 10
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
critic-l2-reg: 0.0003
max-step-num: 2500000000
gamma: 0.955
render-eval: False
gating-index: None
epoch-step-num: 5000000
interpolation: False
tau: 0.001
total-step-num: 2500000000
loss-output-smooth-coeff: 1.0
max-episode-num: 5000000
record-start-size: 10000.0
max-path-num: 20
Physics-frequency: 1000
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
prioritized-exp-replay: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
joint-interpolation: True
max-test-time: 10
dsr-gait-period: 0.6
loss-output-diff-coeff: 0
rollout-step-num: 1
imitation-weight: 0.5
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
